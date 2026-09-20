<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/m9h8nyf8o.css';
import '../../css/g/gxvallb2k.css';
import '../../css/n/nohfypbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="m9h8nyf8o"/><path class="gxvallb2k"/><path class="nohfypbva"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:server-2" /></template>
