<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/cpgy2mbct.css';
import '../../css/e/e5b98zs_u.css';
import '../../css/h/hm9_r3b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="cpgy2mbct"/><path class="e5b98zs_u"/><path class="hm9_r3b6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:security-computer-shield" /></template>
