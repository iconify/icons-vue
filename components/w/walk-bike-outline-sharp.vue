<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfcbt3bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:walk-bike-outline-sharp" /></template>
<style>
.cfcbt3bia {
  fill: currentColor;
  d: path("M4.212 19L6.018 7.875l-2.403.973v2.036h-1.23V8.018l4.338-1.755q.402-.148.786-.013q.383.136.525.501q.075.15.175.618t.404.965t.87.889t1.536.394h.635v1.23h-.635q-.788 0-1.38-.234t-1.204-.648l-.458 2.613l1.889 1.846V19H8.635v-3.884L6.48 13.058L5.46 19zM6.916 5.026q-.378-.378-.378-.93t.378-.94t.93-.387t.92.388t.368.94q0 .551-.368.929t-.92.378t-.93-.378m11.315 15.98q-1.366 0-2.39-.819t-1.347-2.072H11.5l.5-1h2.385q-.008-.857.343-1.61q.35-.753 1.036-1.274h-3.302l.5-1h3.411l-.887-2.692H13.54v-1h2.667l1.248 3.82q.183-.043.379-.06q.196-.016.398-.016q1.606 0 2.748 1.133q1.142 1.132 1.142 2.738t-1.142 2.729t-2.748 1.123m0-.987q1.204 0 2.044-.84t.84-2.044q0-1.187-.825-2.005t-2.007-.841q-.135 0-.26.009q-.125.01-.24.048l.783 2.387l-.958.317l-.783-2.38q-.644.35-1.042 1.004q-.398.655-.398 1.46q0 1.204.83 2.045q.831.84 2.016.84");
}

</style>
