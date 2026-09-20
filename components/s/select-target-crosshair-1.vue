<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/k/kn1acfbpi.css';
import '../../css/f/f69s4vbjl.css';
import '../../css/w/wz1sd4gsh.css';
import '../../css/v/v45rcfbxh.css';
import '../../css/t/t58i-ubmu.css';
import '../../css/s/syh7zz0li.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="kn1acfbpi"/><path class="f69s4vbjl"/><path class="wz1sd4gsh"/><path class="v45rcfbxh"/><path class="t58i-ubmu"/><path class="syh7zz0li"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:select-target-crosshair-1" /></template>
