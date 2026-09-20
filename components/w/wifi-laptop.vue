<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gx3-ulb5j.css';
import '../../css/z/z20-tsb2r.css';
import '../../css/l/l9ep8wyys.css';
import '../../css/q/qtdy2f5jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gx3-ulb5j"/><path class="z20-tsb2r"/><path class="l9ep8wyys"/><path class="qtdy2f5jc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:wifi-laptop" /></template>
