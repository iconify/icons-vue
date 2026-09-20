<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/b45uyl5ow.css';
import '../../css/l/lnz-_8qeq.css';
import '../../css/s/sogihwb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="b45uyl5ow"/><path class="lnz-_8qeq"/><path class="sogihwb-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:money-atm-withdraw" /></template>
