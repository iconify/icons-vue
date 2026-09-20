<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/hmle4qehd.css';
import '../../css/s/sdqlbxbcw.css';
import '../../css/z/zfhw3cbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hmle4qehd"/><path class="sdqlbxbcw"/><path class="zfhw3cbas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:perspective-grid" /></template>
