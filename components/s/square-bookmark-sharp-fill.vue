<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ay4fadcps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-bookmark-sharp-fill" /></template>
<style>
.ay4fadcps {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 2H21C21.552 2 22 2.448 22 3V21C22 21.552 21.552 22 21 22H3C2.448 22 2 21.552 2 21V3C2 2.448 2.448 2 3 2ZM16.747 11.984L16.731 7.298C16.729 6.747 16.282 6.301 15.731 6.301H8.269C7.718 6.301 7.271 6.747 7.269 7.298L7.236 16.669C7.236 17.225 7.684 17.673 8.236 17.673C8.368 17.673 8.499 17.647 8.621 17.596L12 16.19L15.379 17.596C15.501 17.647 15.632 17.673 15.764 17.673C16.316 17.673 16.764 17.225 16.764 16.673L16.747 11.984Z");
}

</style>
