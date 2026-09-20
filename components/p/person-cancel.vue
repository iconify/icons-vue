<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygudxhb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-cancel" /></template>
<style>
.ygudxhb6m {
  fill: currentColor;
  d: path("m17.4 12.308l-.708-.708l2.095-2.1l-2.095-2.075l.708-.713l2.1 2.1l2.075-2.1l.713.713l-2.08 2.075l2.08 2.1l-.713.708l-2.075-2.075zm-10.523-1.8Q6 9.63 6 8.385t.877-2.123T9 5.385t2.123.877T12 8.385t-.877 2.123T9 11.385t-2.123-.877M2 18.616v-1.647q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34t2.837.34t2.832 1.018q.61.298.97.838q.361.539.361 1.158v1.646z");
}

</style>
