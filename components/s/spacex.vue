<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxs996u1a.css';
import '../../css/w/wyay58blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxs996u1a"/><path class="wyay58blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:spacex" /></template>
