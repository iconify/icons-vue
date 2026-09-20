<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqirzsbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-doorbell-visitor-outline" /></template>
<style>
.xqirzsbdd {
  fill: currentColor;
  d: path("M16.934 16.566q-.434-.433-.434-1.066t.434-1.066T18 14t1.066.434q.434.433.434 1.066t-.434 1.066Q18.633 17 18 17t-1.066-.434M14.5 21.5v-.575q0-.85.975-1.388T18 19t2.525.538t.975 1.387v.575zm2-9.5h-1V7q0-1.506-1.044-2.503T12 3.5t-2.456.997T8.5 7v10q0 1.412 1.044 2.456T12 20.5v1q-1.894 0-3.197-1.303T7.5 17V7q0-1.894 1.303-3.197T12 2.5t3.197 1.303T16.5 7zm-3.165-2.664q.55-.55.55-1.336t-.55-1.335T12 6.115t-1.336.55T10.117 8t.549 1.336T12 9.885t1.336-.55m-2.672 8q.55.55 1.336.55t1.336-.55t.549-1.335t-.55-1.336T12 14.117t-1.336.549T10.117 16t.549 1.336m.524-.571q-.304-.352-.304-.765t.304-.765q.303-.35.811-.35t.812.303t.304.812q0 .414-.304.765q-.304.35-.812.35t-.811-.35");
}

</style>
