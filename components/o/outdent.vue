<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_q-6vbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_q-6vbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:outdent" /></template>
