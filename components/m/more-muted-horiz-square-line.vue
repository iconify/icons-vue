<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj46-921z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj46-921z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:more-muted-horiz-square-line" /></template>
