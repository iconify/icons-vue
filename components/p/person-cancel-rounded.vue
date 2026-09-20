<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edz6i91ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-cancel-rounded" /></template>
<style>
.edz6i91ch {
  fill: currentColor;
  d: path("m19.5 10.233l-1.746 1.72q-.14.141-.342.154t-.366-.153q-.16-.16-.16-.354t.16-.354l1.74-1.746l-1.74-1.721q-.16-.14-.16-.341t.16-.367q.166-.165.357-.165t.357.165l1.74 1.74l1.721-1.745q.14-.166.342-.166t.366.166t.165.356t-.165.357L20.208 9.5l1.727 1.746q.146.146.153.344q.006.199-.16.364q-.165.16-.353.162q-.189.003-.354-.162zm-12.623.275Q6 9.63 6 8.385t.877-2.123T9 5.385t2.123.877T12 8.385t-.877 2.123T9 11.385t-2.123-.877M2 17.577v-.608q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34t2.837.34t2.832 1.018q.61.298.97.838q.361.539.361 1.158v.608q0 .44-.299.74q-.299.298-.74.298H3.04q-.441 0-.74-.299t-.3-.739");
}

</style>
