<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5llwvbom.css';
import '../../css/m/moizz8y3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g5llwvbom"/><path class="moizz8y3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:upload-48-bold" /></template>
