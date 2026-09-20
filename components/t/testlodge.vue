<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":219};
const content = `<path class="dnd6_cbrm"/><path class="ojbbyxbvv"/><path class="fha9iqh8l"/><path class="sx7k4opbj"/><path class="sxp-tjbcu"/><path class="b6yos_bkj"/><path class="jt91he6ci"/><path class="z97z1wb4n"/><path class="x6m-zbcge"/><path class="thoas95ga"/><path class="gxlcz7p1l"/><path class="hk-cvbbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:testlodge" /></template>
<style>
.b6yos_bkj {
  fill: var(--svg-color--008ca9, #008ca9);
  d: path("m0 7.569l113.115 52.883l-3.073 1.243L3.018 75.98L0 75.467z");
}

.dnd6_cbrm {
  fill: var(--svg-color--c5cf21, #c5cf21);
  d: path("M256 7.569L142.885 60.452l3.073 1.243L252.982 75.98l3.018-.513z");
}

.fha9iqh8l {
  fill: var(--svg-color--006d69, #006d69);
  d: path("m203.357 105.92l-60.472-45.468l.44 4.024l42.495 129.038l2.95 2.312z");
}

.gxlcz7p1l {
  fill: var(--svg-color--70b540, #70b540);
  d: path("m67.229 195.826l60.768 22.952l-14.882-158.326z");
}

.hk-cvbbzb {
  fill: var(--svg-color--008ca9, #008ca9);
  d: path("M128.146 38.006L218.79 0L256 7.569z");
}

.jt91he6ci {
  fill: var(--svg-color--006d69, #006d69);
  d: path("M127.982 38.006V14.868L218.79 0l-1.582 1.402l-85.818 35.563z");
}

.ojbbyxbvv {
  fill: var(--svg-color--70b540, #70b540);
  d: path("M256 75.467L142.885 60.452l1.891 2.78l55.969 42.391l2.612.297z");
}

.sx7k4opbj {
  fill: var(--svg-color--008ca9, #008ca9);
  d: path("m188.77 195.826l-60.773 22.952l14.888-158.326z");
}

.sxp-tjbcu {
  fill: var(--svg-color--70b540, #70b540);
  d: path("m127.982 38.006l.311-.596l.07-22.053l-.381-.489L37.21 0l1.582 1.402l85.818 35.563z");
}

.thoas95ga {
  fill: var(--svg-color--c5cf21, #c5cf21);
  d: path("m52.643 105.92l60.472-45.468l-.44 4.024L70.18 193.514l-2.951 2.312z");
}

.x6m-zbcge {
  fill: var(--svg-color--006d69, #006d69);
  d: path("m0 75.467l113.115-15.015l-1.891 2.78l-55.969 42.391l-2.612.297z");
}

.z97z1wb4n {
  fill: var(--svg-color--c5cf21, #c5cf21);
  d: path("M127.854 38.006L37.21 0L0 7.569z");
}

</style>
