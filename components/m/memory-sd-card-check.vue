<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fnj-t_blw.css';
import '../../css/p/pe5-nx9op.css';
import '../../css/z/zk27gtbyf.css';
import '../../css/q/qvs2fhg4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="fnj-t_blw"/><path class="pe5-nx9op"/><path class="zk27gtbyf"/><path class="qvs2fhg4n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:memory-sd-card-check" /></template>
