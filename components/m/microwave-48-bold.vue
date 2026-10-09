<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/defz0cbcm.css';
import '../../css/o/oxmy0inzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="defz0cbcm"/><path class="oxmy0inzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:microwave-48-bold" /></template>
