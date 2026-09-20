<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6dpxtbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:recent-patient" /></template>
<style>
.k6dpxtbsf {
  fill: currentColor;
  d: path("M5 18.616v-1.647q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34q.673 0 1.346.076t1.346.248v4.677zm4.877-8.108Q9 9.63 9 8.385t.877-2.123T12 5.385t2.123.877T15 8.385t-.877 2.123t-2.123.877t-2.123-.877M18.5 22.116v-3.808h-1.423V13.5h4.115l-1.826 3.616h1.769z");
}

</style>
