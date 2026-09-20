<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGSFQJOgjT"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="di_wrxb0a"/><path clip-rule="evenodd" class="jl7irzb8p"/><path clip-rule="evenodd" class="x2jb-lbgi"/><path clip-rule="evenodd" class="nhri-xbtf"/></g></mask></defs><circle mask="url(#SVGSFQJOgjT)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:question-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.di_wrxb0a {
  d: path("M14.739 19.213a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

.ft5dv1b6b {
  fill: none;
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.jl7irzb8p {
  fill-rule: evenodd;
  d: path("M12.71 7.765c-.67 0-1.245.2-1.65.486c-.39.276-.583.597-.639.874a1.45 1.45 0 0 1-2.842-.574c.227-1.126.925-2.045 1.809-2.67c.92-.65 2.086-1.016 3.322-1.016c2.557 0 5.208 1.71 5.208 4.456c0 1.59-.945 2.876-2.169 3.626a1.45 1.45 0 0 1-1.514-2.474c.57-.349.783-.794.783-1.152c0-.574-.715-1.556-2.308-1.556");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.nhri-xbtf {
  fill-rule: evenodd;
  d: path("M16.239 10.966a1.45 1.45 0 0 1-.5 1.99l-2.284 1.367a1.45 1.45 0 0 1-1.49-2.488l2.285-1.368a1.45 1.45 0 0 1 1.989.5");
}

.x2jb-lbgi {
  fill-rule: evenodd;
  d: path("M12.71 11.63c.8 0 1.45.648 1.45 1.45v1.502a1.45 1.45 0 1 1-2.9 0V13.08c0-.8.649-1.45 1.45-1.45");
}

</style>
