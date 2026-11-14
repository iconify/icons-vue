<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlksyxgfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tote-bin" /></template>
<style>
.nlksyxgfj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m2.924 7.52l2.5-3q.107-.128.258-.199T6 4.25h12q.167 0 .318.071t.258.199l2.5 3q.084.1.128.223q.045.122.046.253V8q0 .034-.003.068l-.003.025v.001l-1.5 11.999q-.008.067-.029.132q-.02.065-.052.125t-.074.114t-.093.098t-.109.08t-.122.059q-.063.025-.13.037T19 20.75H5q-.068 0-.135-.012t-.13-.037q-.064-.024-.122-.059t-.109-.08t-.093-.098t-.074-.114t-.052-.125q-.021-.065-.029-.132l-1.5-12q-.02-.155.024-.304t.144-.269m14.725-1.77H6.351l-1.25 1.5h13.798zm-7.399 4.5q-2 0-2 2t2 2h3.5q2 0 2-2t-2-2z");
}

</style>
