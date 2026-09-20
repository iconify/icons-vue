<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvqgz7yqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-cancel-outline-sharp" /></template>
<style>
.lvqgz7yqc {
  fill: currentColor;
  d: path("m17.4 12.308l-.708-.708l2.095-2.1l-2.095-2.075l.708-.713l2.1 2.1l2.075-2.1l.713.713l-2.08 2.075l2.08 2.1l-.713.708l-2.075-2.075zm-10.523-1.8Q6 9.63 6 8.385t.877-2.123T9 5.385t2.123.877T12 8.385t-.877 2.123T9 11.385t-2.123-.877M2 18.616v-1.647q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34t2.837.34t2.832 1.018q.61.298.97.838q.361.539.361 1.158v1.646zm1-1h12v-.647q0-.332-.215-.625q-.214-.292-.593-.494q-1.234-.598-2.542-.916T9 14.616t-2.65.318t-2.542.916q-.38.202-.593.494Q3 16.637 3 16.97zm7.413-7.819Q11 9.21 11 8.385t-.587-1.413T9 6.385t-1.412.587T7 8.385t.588 1.412T9 10.385t1.413-.588M9 17.616");
}

</style>
