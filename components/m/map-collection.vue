<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wk9wetb5e.css';
import '../../css/d/dn45p3vty.css';
import '../../css/j/j2msh4wvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wk9wetb5e"/><path class="dn45p3vty"/><path class="j2msh4wvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-collection" /></template>
