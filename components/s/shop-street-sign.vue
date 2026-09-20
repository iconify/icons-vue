<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wxwloacjj.css';
import '../../css/v/vy3x4abmt.css';
import '../../css/b/bgbwufb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="wxwloacjj"/><path class="vy3x4abmt"/><path class="bgbwufb-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:shop-street-sign" /></template>
