<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/u/uu_7a4y3p.css';
import '../../css/z/zv6cqnbnp.css';
import '../../css/q/qsu9n_98r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uu_7a4y3p"/><circle class="zv6cqnbnp"/><path class="qsu9n_98r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:map-pin-minus" /></template>
