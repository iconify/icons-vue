<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="briotttqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:phonelink-off-outline-sharp" /></template>
<style>
.briotttqm {
  fill: currentColor;
  d: path("m8.83 6l-1-1H20v1zm12.19 12.154l-1-1v-7.77h-4.77v3.035l-1-1V8.385h6.77zm-1.086 3.215L17.566 19H14.25v-3.315L6 7.435V17.5h5.48V19H3v-1.5h2V6.435L2.766 4.2l.707-.708l17.17 17.17zm-2.3-6.582");
}

</style>
