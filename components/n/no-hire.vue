<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_8yiob5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:no-hire" /></template>
<style>
.v_8yiob5r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 14.25q.859 0 1.423-.295l3.414 6.146q.705 1.388 2.441.867q1.722-.516 1.722-2.468v-3.25h5q1.242.01 2.071-.923t.673-2.171l-.006-.038l-1.246-6.982q-.313-2.405-2.748-2.386H6.5q-.084 0-.166.019q-.082.018-.158.055q-.076.036-.142.088q-.066.053-.119.118q-.524-.28-1.165-.28h-.5q-1.036 0-1.768.732T1.75 5.25v6.5q0 2.5 2.5 2.5z");
}

</style>
