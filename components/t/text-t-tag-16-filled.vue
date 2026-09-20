<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lqojhhbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-t-tag-16-filled" /></template>
<style>
.lqojhhbnp {
  fill: currentColor;
  d: path("M12.001 4.75v-1a.75.75 0 0 0-.75-.75h-6.5a.75.75 0 0 0-.75.75v1a.75.75 0 0 0 1.5 0V4.5h1.75v7h-.25a.75.75 0 0 0 0 1.5h2a.75.75 0 0 0 0-1.5h-.25v-7h1.75v.25a.75.75 0 0 0 1.5 0M4.249 6.689a.75.75 0 0 0-1.06.062l-2 2.25a.75.75 0 0 0 0 .996l2 2.25a.747.747 0 0 0 1.06.063a.75.75 0 0 0 .062-1.059L2.754 9.499L4.31 7.747a.75.75 0 0 0-.062-1.058m8.563.063l2 2.25v.001a.75.75 0 0 1 0 .996l-2 2.25a.75.75 0 1 1-1.121-.996l1.557-1.752l-1.557-1.752a.749.749 0 1 1 1.121-.997");
}

</style>
