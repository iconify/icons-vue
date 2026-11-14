<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i--oycc2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:team-outing" /></template>
<style>
.i--oycc2m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m20.187 16.524l-6.008-10.68Q13.462 4.57 12 4.57T9.821 5.844l-6.008 10.68q-.703 1.25.021 2.488t2.158 1.238h3.007q-.177 0-.334-.079q-.066-.033-.125-.079q-.058-.045-.107-.101q-.048-.055-.085-.12q-.036-.064-.06-.134q-.023-.07-.032-.143t-.004-.147t.025-.145t.052-.137l3-6q.033-.066.079-.125q.045-.058.101-.107q.055-.048.12-.085q.064-.036.134-.06q.07-.023.143-.032t.147-.004t.145.025t.137.052q.109.055.195.141t.141.195l3 6q.067.133.077.282q.011.149-.036.29q-.048.142-.145.254q-.098.113-.232.18q-.157.079-.334.079h3.007q1.434 0 2.158-1.238t.021-2.488m-5.188 3.726q-.121 0-.236-.038q-.142-.048-.254-.145q-.113-.098-.18-.232L12 15.177l-2.329 4.658q-.067.134-.18.232q-.112.097-.254.145q-.115.038-.236.038z");
}

</style>
