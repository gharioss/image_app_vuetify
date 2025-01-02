<template>
    <VNavigationDrawer
        expand-on-hover
        rail
      >
        <VList>
          <VListItem
            prepend-avatar="https://randomuser.me/api/portraits/women/85.jpg"
            subtitle="sandra_a88@gmailcom"
            title="Sandra Adams"
          ></VListItem>
        </VList>

        <VDivider></VDivider>

        <VList density="compact" nav>
            <v-icon icon="$vuetify"></v-icon>
          <VListItem prepend-icon="mdi-image" title="My Files" value="myfiles"></VListItem>
          <VListItem prepend-icon="mdi-account-multiple" title="Shared with me" value="shared"></VListItem>
          <VListItem prepend-icon="mdi-star" title="Starred" value="starred"></VListItem>
        </VList>
      </VNavigationDrawer>
</template>