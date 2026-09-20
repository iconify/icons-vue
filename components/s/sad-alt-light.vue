<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/p/p058992qq.css';
import '../../css/i/i4d76icce.css';
import '../../css/k/kdp6-qbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><circle class="p058992qq"/><path class="i4d76icce"/><path class="kdp6-qbqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:sad-alt-light" /></template>
