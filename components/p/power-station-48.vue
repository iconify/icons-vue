<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1j5nsboq.css';
import '../../css/p/pwrb__blp.css';
import '../../css/q/qrfic8bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j1j5nsboq"/><path class="pwrb__blp"/><path class="qrfic8bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-station-48" /></template>
