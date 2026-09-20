<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyfxqwbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:no-meeting-room-sharp" /></template>
<style>
.eyfxqwbdv {
  fill: currentColor;
  d: path("m17 14.189l-1-1V6h-2v5.189L6.85 4H14v1h3zm2.492 6.719L14 15.416V20H4v-1h2V7.416L3.092 4.508L3.8 3.8l16.4 16.4z");
}

</style>
