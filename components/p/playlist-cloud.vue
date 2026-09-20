<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/d0g1dp0cg.css';
import '../../css/i/izpy64bue.css';
import '../../css/l/llbe05l9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="d0g1dp0cg"/><path class="izpy64bue"/><path class="llbe05l9e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:playlist-cloud" /></template>
