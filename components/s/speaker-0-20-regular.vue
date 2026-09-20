<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ec-eqyb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:speaker-0-20-regular" /></template>
<style>
.ec-eqyb1o {
  fill: currentColor;
  d: path("M11.996 3.006c0-.873-1.04-1.327-1.68-.733L6.444 5.866a.5.5 0 0 1-.34.134H3.496a1.5 1.5 0 0 0-1.5 1.5v5a1.5 1.5 0 0 0 1.5 1.5h2.608a.5.5 0 0 1 .34.133l3.872 3.594c.64.593 1.68.14 1.68-.733zM7.124 6.599l3.872-3.593v13.988L7.124 13.4a1.5 1.5 0 0 0-1.02-.4H3.496a.5.5 0 0 1-.5-.5v-5a.5.5 0 0 1 .5-.5h2.608a1.5 1.5 0 0 0 1.02-.4");
}

</style>
