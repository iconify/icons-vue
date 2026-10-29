<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mun6vbc9f.css';
import '../../css/g/gs5m2mmri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mun6vbc9f wm-k"/><path class="gs5m2mmri wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:square-x" /></template>
