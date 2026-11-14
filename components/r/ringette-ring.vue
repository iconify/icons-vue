<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k73n5543e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ringette-ring" /></template>
<style>
.k73n5543e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.538 11.461l7.523-8.463q.049-.055.086-.119q.037-.063.062-.133q.024-.07.034-.143t.006-.147q-.005-.074-.023-.145q-.019-.072-.051-.138t-.077-.126q-.045-.058-.1-.108q-.111-.099-.252-.148t-.29-.04t-.283.074t-.234.177l-7.471 8.405Q10.974 9.25 9 9.25q-2.382 0-4.066 1.684T3.25 15t1.684 4.066T9 20.75t4.066-1.684T14.75 15q0-2.02-1.212-3.539M9 12.25q2.75 0 2.75 2.75T9 17.75T6.25 15T9 12.25");
}

</style>
