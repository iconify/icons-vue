<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/b/b5cxlbb9z.css';
import '../../css/s/s1i6yv5uk.css';
import '../../css/k/k-e2t9i7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="b5cxlbb9z"/><path class="s1i6yv5uk"/><path class="k-e2t9i7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:pressure-light" /></template>
