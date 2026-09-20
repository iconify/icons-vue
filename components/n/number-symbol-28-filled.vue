<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ke3-pqb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:number-symbol-28-filled" /></template>
<style>
.ke3-pqb7f {
  fill: currentColor;
  d: path("M12.98 3.2a1 1 0 1 0-1.96-.4L9.752 9H4a1 1 0 1 0 0 2h5.343l-1.227 6H3a1 1 0 1 0 0 2h4.707L6.52 24.8a1 1 0 1 0 1.96.4L9.748 19h5.959l-1.187 5.8a1 1 0 1 0 1.96.4l1.268-6.2H23a1 1 0 1 0 0-2h-4.843l1.227-6H24a1 1 0 1 0 0-2h-4.207l1.187-5.8a1 1 0 1 0-1.96-.4L17.752 9h-5.959zM16.116 17h-5.959l1.227-6h5.959z");
}

</style>
