<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/yztdgircs.css';
import '../../css/h/hwcdu9nye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="yztdgircs"/><path vector-effect="non-scaling-stroke" class="hwcdu9nye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:preformatted" /></template>
