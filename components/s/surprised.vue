<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gshe_di8n.css';
import '../../css/z/zjgyanbqn.css';
import '../../css/f/fecpnosez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gshe_di8n"/><path class="zjgyanbqn"/><path class="fecpnosez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:surprised" /></template>
