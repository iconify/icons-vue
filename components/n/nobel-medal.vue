<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r51bxs_eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:nobel-medal" /></template>
<style>
.r51bxs_eq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.084 8.691q1.008.499 1.867 1.358Q19.001 12.1 19 15q.001 2.9-2.049 4.951Q14.9 22.002 12 22.002t-4.951-2.051T5 15q-.001-2.9 2.049-4.951q.859-.859 1.867-1.358L6.319 3.064q-.031-.067-.048-.139q-.017-.071-.02-.145t.008-.147q.012-.073.037-.142q.026-.07.064-.133t.089-.117t.11-.098t.127-.074Q6.835 2 7 2h10q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .165-.069.314zm-4.75-.508q.794-.185 1.666-.185t1.666.185L15.828 3.5H8.172zM8.25 15q0 3.75 3.75 3.75T15.75 15T12 11.25T8.25 15");
}

</style>
