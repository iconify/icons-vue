<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/d15_2pb5h.css';
import '../../css/g/gnfv7ibas.css';
import '../../css/q/qevel6bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="d15_2pb5h"/><path class="gnfv7ibas"/><path class="qevel6bmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:microphone" /></template>
