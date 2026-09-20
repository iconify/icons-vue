<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="zto0y-b_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vip-28-filled" /></template>
<style>
.zto0y-b_c {
  fill: currentColor;
  d: path("M22.25 4A3.75 3.75 0 0 1 26 7.75v12.5A3.75 3.75 0 0 1 22.25 24H5.75A3.75 3.75 0 0 1 2 20.25V7.75A3.75 3.75 0 0 1 5.75 4zm-9.958 6.06a.75.75 0 0 0-.982.398L9 15.915l-2.31-5.457a.75.75 0 1 0-1.38.584l2.652 6.27a1.128 1.128 0 0 0 2.076 0l2.652-6.27a.75.75 0 0 0-.398-.982M14.75 10a.75.75 0 0 0-.75.75v6.5a.75.75 0 0 0 1.5 0v-6.5a.75.75 0 0 0-.75-.75m3.5 0a.75.75 0 0 0-.75.75v6.5a.75.75 0 0 0 1.5 0V15.5h1.25a2.75 2.75 0 1 0 0-5.5zm2 1.5a1.25 1.25 0 1 1 0 2.5H19v-2.5z");
}

</style>
