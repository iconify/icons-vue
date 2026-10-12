<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i29j_x8py.css';
import '../../css/z/zf0u2_bci.css';
import '../../css/j/jjbxq_b8w.css';
import '../../css/x/xxbbvx_gg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i29j_x8py"/><path class="zf0u2_bci"/><path class="jjbxq_b8w"/><path class="xxbbvx_gg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:skull-duotone" /></template>
