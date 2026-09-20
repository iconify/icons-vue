<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n9l5e8mcr.css';
import '../../css/a/a-ewrneoj.css';
import '../../css/r/r6v1ktpdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="n9l5e8mcr"/><path class="a-ewrneoj"/><path class="r6v1ktpdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:swimming-pool-person" /></template>
