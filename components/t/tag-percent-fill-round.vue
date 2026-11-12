<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtr64fbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-percent-fill-round" /></template>
<style>
.gtr64fbsm {
  fill: currentColor;
  d: path("M20 19a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V8c0-1.039.578-1.992 1.293-2.707l2-2C8.008 2.578 8.961 2 10 2h4c1.039 0 1.992.578 2.707 1.293l2 2C19.422 6.008 20 6.961 20 8ZM13 5h-2a1 1 0 0 0 0 2h2a1 1 0 0 0 0-2m-5.842 6.221a2 2 0 1 0 3.684 1.558a2 2 0 0 0-3.684-1.558m2.549 7.486l6-6a.999.999 0 1 0-1.414-1.414l-6 6a.999.999 0 1 0 1.414 1.414m6.072 1.135a2 2 0 1 0-1.558-3.684a2 2 0 0 0 1.558 3.684");
}

</style>
