<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/v/vbzbqg9av.css';
import '../../css/x/x1vm6db2y.css';
import '../../css/x/xsb0bgv9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vbzbqg9av"/><path class="x1vm6db2y"/><path class="xsb0bgv9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:restart-broken" /></template>
