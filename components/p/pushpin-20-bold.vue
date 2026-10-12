<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktghhy0et.css';
import '../../css/e/ept6rpbfu.css';
import '../../css/g/ga3wfsbxu.css';
import '../../css/v/vz2ceoucx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ktghhy0et"/><path class="ept6rpbfu"/><path class="ga3wfsbxu"/><path class="vz2ceoucx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pushpin-20-bold" /></template>
