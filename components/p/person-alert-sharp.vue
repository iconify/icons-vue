<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba7nsybuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-alert-sharp" /></template>
<style>
.ba7nsybuc {
  fill: currentColor;
  d: path("M19.48 10.52q-.21-.21-.21-.52t.21-.52t.52-.21t.52.21t.21.52t-.21.52t-.52.21t-.52-.21m.02-3.02v-4h1v4zM6.877 10.508Q6 9.63 6 8.385t.877-2.123T9 5.385t2.123.877T12 8.385t-.877 2.123T9 11.385t-2.123-.877M2 18.616v-1.647q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34t2.837.34t2.832 1.018q.61.298.97.838q.361.539.361 1.158v1.646z");
}

</style>
