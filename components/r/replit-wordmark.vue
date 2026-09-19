<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8dwnefac.css';
import '../../css/v/vsi_9nbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="d8dwnefac"/><path class="vsi_9nbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:replit-wordmark" /></template>
