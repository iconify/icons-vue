<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oszrpqbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-left-48-filled" /></template>
<style>
.oszrpqbzl {
  fill: currentColor;
  d: path("M7.228 27.528c-2.99-1.617-2.966-5.915.042-7.499L36.772 4.495c2.83-1.49 6.23.562 6.23 3.76v31.488c0 3.22-3.44 5.27-6.272 3.739z");
}

</style>
