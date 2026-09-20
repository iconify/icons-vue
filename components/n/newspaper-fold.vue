<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lyfpph83j.css';
import '../../css/i/ibyph9b4f.css';
import '../../css/s/s2oty211w.css';
import '../../css/o/oeds6acur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="lyfpph83j"/><path class="ibyph9b4f"/><path class="s2oty211w"/><path class="oeds6acur"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:newspaper-fold" /></template>
