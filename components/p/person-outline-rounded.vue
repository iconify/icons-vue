<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mab59rbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-outline-rounded" /></template>
<style>
.mab59rbfq {
  fill: currentColor;
  d: path("M9.877 10.508Q9 9.63 9 8.385t.877-2.123T12 5.385t2.123.877T15 8.385t-.877 2.123t-2.123.877t-2.123-.877M5 17.577v-.608q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34t2.837.34t2.832 1.018q.61.298.97.838q.361.539.361 1.158v.608q0 .44-.299.74q-.299.298-.74.298H6.04q-.441 0-.74-.299t-.3-.739m1 .039h12v-.647q0-.332-.215-.625q-.214-.292-.593-.494q-1.234-.598-2.542-.916T12 14.616t-2.65.318t-2.542.916q-.38.202-.593.494Q6 16.637 6 16.97zm7.413-7.819Q14 9.21 14 8.385t-.587-1.413T12 6.385t-1.412.587T10 8.385t.588 1.412t1.412.588t1.413-.588M12 17.616");
}

</style>
