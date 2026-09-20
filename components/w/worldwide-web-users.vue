<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/cnydaccbe.css';
import '../../css/a/ai3u1bbps.css';
import '../../css/i/imx1lsbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="cnydaccbe"/><path class="ai3u1bbps"/><path class="imx1lsbhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:worldwide-web-users" /></template>
