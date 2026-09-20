<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qf_kb0bbs.css';
import '../../css/a/a4gmabcpu.css';
import '../../css/m/mzxbdgbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qf_kb0bbs"/><path class="a4gmabcpu"/><path class="mzxbdgbpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:vectors-path-flat" /></template>
