<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pe0nlyboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:seat-perch" /></template>
<style>
.pe0nlyboi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 2.75H8Q5.75 2.75 5.75 5q0 2.061 1.888 2.234l-1.88 13.16q-.022.148.015.292q.037.145.127.264t.218.195t.276.097q.073.011.147.007t.145-.022q.072-.019.138-.051t.126-.076q.059-.044.108-.099q.05-.055.087-.119q.038-.063.063-.133q.024-.07.034-.143l.694-4.856h8.128l.694 4.856q.01.073.034.143q.025.07.063.133q.037.064.087.119t.108.099q.059.044.126.076q.066.032.138.051q.071.018.145.022t.147-.007t.143-.034q.07-.025.133-.063q.064-.037.119-.087t.099-.108q.044-.059.076-.126q.032-.066.051-.138q.018-.071.022-.145t-.007-.147l-1.88-13.16Q18.25 7.061 18.25 5q0-2.25-2.25-2.25m-.15 11.5h-7.7l1-7h5.7z");
}

</style>
