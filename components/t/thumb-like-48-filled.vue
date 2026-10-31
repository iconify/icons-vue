<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j_7njabbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:thumb-like-48-filled" /></template>
<style>
.j_7njabbv {
  fill: currentColor;
  d: path("M21.927 5.658c.491-1.948 2.643-3.222 4.628-2.4c.144.06.285.116.426.185c.135.067.317.166.53.3c.422.269.973.686 1.519 1.3c1.11 1.25 2.14 3.24 2.14 6.24c0 1.569-.311 3.657-.605 5.291A70 70 0 0 1 30.29 18h2.455c4.545 0 7.97 4.135 7.124 8.6l-1.563 8.242c-1.224 6.451-7.69 10.488-14.022 8.755L10.342 39.78a6.25 6.25 0 0 1-4.497-4.901l-.746-4.072c-.584-3.19 1.387-6.07 4.012-7.435c8.463-4.4 11.702-13.294 12.816-17.715");
}

</style>
