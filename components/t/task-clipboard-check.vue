<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/g5h1v8b-m.css';
import '../../css/n/nxc97uq5g.css';
import '../../css/b/bny-iu66i.css';
import '../../css/v/vkezfyhjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="g5h1v8b-m"/><path class="nxc97uq5g"/><path class="bny-iu66i"/><path class="vkezfyhjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:task-clipboard-check" /></template>
