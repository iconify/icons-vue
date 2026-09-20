<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/a/azg4gk7yy.css';
import '../../css/r/rkfprj2os.css';
import '../../css/x/xxv23h4tl.css';
import '../../css/g/g_fi3zbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="azg4gk7yy"/><path class="rkfprj2os"/><path class="xxv23h4tl"/><path class="g_fi3zbow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:wireless-tower-building" /></template>
