<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esqg6lffk.css';
import '../../css/m/m_dyr3b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="esqg6lffk"/><path class="m_dyr3b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:power" /></template>
