<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gq0wg3b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-new-48-regular" /></template>
<style>
.gq0wg3b6x {
  fill: currentColor;
  d: path("M35.75 6A6.25 6.25 0 0 1 42 12.25v18.5a6.25 6.25 0 0 1-5.106 6.144A6.25 6.25 0 0 1 30.75 42h-14.5C10.59 42 6 37.41 6 31.75v-14.5c0-3.06 2.2-5.607 5.105-6.145A6.25 6.25 0 0 1 17.25 6zM11 13.714a3.75 3.75 0 0 0-2.5 3.536v14.5a7.75 7.75 0 0 0 7.75 7.75h14.5a3.75 3.75 0 0 0 3.535-2.5H17.25A6.25 6.25 0 0 1 11 30.75zM17.25 8.5a3.75 3.75 0 0 0-3.75 3.75v18.5a3.75 3.75 0 0 0 3.75 3.75h18.5a3.75 3.75 0 0 0 3.75-3.75v-18.5a3.75 3.75 0 0 0-3.75-3.75zm15.5 5.5c.69 0 1.25.56 1.25 1.25v9.5a1.25 1.25 0 1 1-2.5 0v-6.482L21.134 28.634a1.25 1.25 0 0 1-1.768-1.768L29.732 16.5H23.25a1.25 1.25 0 1 1 0-2.5z");
}

</style>
