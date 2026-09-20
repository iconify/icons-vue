<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/j/j80x_6w1a.css';
import '../../css/r/r3uw8bcwl.css';
import '../../css/i/ixd243bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="j80x_6w1a"/><path class="r3uw8bcwl"/><path class="ixd243bqj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:responsive-design-expand" /></template>
