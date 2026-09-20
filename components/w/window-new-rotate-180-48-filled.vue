<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o_-6ikw0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-new-rotate-180-48-filled" /></template>
<style>
.o_-6ikw0y {
  fill: currentColor;
  d: path("M12.25 42A6.25 6.25 0 0 1 6 35.75v-18.5a6.25 6.25 0 0 1 5.106-6.144A6.25 6.25 0 0 1 17.25 6h14.5C37.41 6 42 10.59 42 16.25v14.5c0 3.06-2.2 5.607-5.105 6.145A6.25 6.25 0 0 1 30.75 42zM37 34.286a3.75 3.75 0 0 0 2.5-3.536v-14.5a7.75 7.75 0 0 0-7.75-7.75h-14.5a3.75 3.75 0 0 0-3.535 2.5H30.75A6.25 6.25 0 0 1 37 17.25zM24.75 34a1.25 1.25 0 1 0 0-2.5h-6.482l10.366-10.366a1.25 1.25 0 0 0-1.768-1.768L16.5 29.732V23.25a1.25 1.25 0 1 0-2.5 0v9.5c0 .69.56 1.25 1.25 1.25z");
}

</style>
