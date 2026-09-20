<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dya8ib-fm.css';
import '../../css/g/gu0vjlbyc.css';
import '../../css/f/fja6vyb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dya8ib-fm"/><path class="gu0vjlbyc"/><path class="fja6vyb6u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:retouch-sticker" /></template>
