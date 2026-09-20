<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zylfzysye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sell-outline-sharp" /></template>
<style>
.zylfzysye {
  fill: currentColor;
  d: path("M12.998 21.671L3 11.692V3h8.692l9.993 10.004zm0-1.421l7.266-7.265l-8.998-8.966H4v7.266zM6.55 7.558q.421 0 .715-.292t.293-.708q0-.425-.292-.722t-.708-.297q-.425 0-.722.295t-.297.716t.295.715t.716.293m5.585 4.577");
}

</style>
