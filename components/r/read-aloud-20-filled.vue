<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="irkv1ybtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:read-aloud-20-filled" /></template>
<style>
.irkv1ybtn {
  fill: currentColor;
  d: path("M11.842 2.141a.75.75 0 0 1 1.017-.3c1.954 1.067 4.85 3.243 5.386 8.076a.75.75 0 1 1-1.49.166c-.463-4.167-2.901-5.99-4.614-6.924a.75.75 0 0 1-.3-1.018M8.694 4.216a.75.75 0 0 0-1.388 0l-4.5 11a.75.75 0 0 0 1.388.568L5.64 12.25h4.72l1.446 3.534a.75.75 0 0 0 1.388-.568zm1.053 6.534H6.254L8 6.48zm2.625-6.401a.75.75 0 0 0-.744 1.302c1.523.87 2.408 2.403 2.63 3.955a.75.75 0 1 0 1.484-.212c-.278-1.948-1.393-3.916-3.37-5.045");
}

</style>
