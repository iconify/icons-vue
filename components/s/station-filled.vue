<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mspp6ty_p.css';
import '../../css/e/eawnq8bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mspp6ty_p"/><path class="eawnq8bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:station-filled" /></template>
