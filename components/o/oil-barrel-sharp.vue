<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkqo8xb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:oil-barrel-sharp" /></template>
<style>
.nkqo8xb6h {
  fill: currentColor;
  d: path("M3.98 20v-1h1.712v-6.5H3.981v-1h1.711V5H3.981V4H20v1h-1.692v6.5H20v1h-1.692V19H20v1zm9.79-5.353q.73-.72.73-1.74q0-.813-.469-1.396T12 9.116q-1.548 1.803-2.024 2.395t-.476 1.4q0 1.018.729 1.736q.728.719 1.769.719t1.771-.72");
}

</style>
