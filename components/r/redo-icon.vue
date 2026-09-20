<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaz_p7cgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qaz_p7cgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:redo-icon" /></template>
