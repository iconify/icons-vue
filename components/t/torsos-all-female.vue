<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4vczpcbl.css';
import '../../css/q/qy0mhroxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="d4vczpcbl"/><path class="qy0mhroxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:torsos-all-female" /></template>
