<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="if_qi7bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:waxing-gibbous-moon" /></template>
<style>
.if_qi7bqn {
  fill: currentColor;
  d: path("M62 32C62 15.432 48.569 2 32.001 2H32C15.432 2 2 15.432 2 32s13.432 30 30 30h.001C48.569 62 62 48.568 62 32M32 60c-2.568 0-5.053-.353-7.415-1c-5.673-4.862-9.584-15.124-9.584-27s3.911-22.138 9.584-27c2.362-.647 4.847-1 7.415-1c15.465 0 28 12.536 28 28S47.465 60 32 60");
}

</style>
