<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irg2cubto.css';
import '../../css/y/yzp037bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irg2cubto"/><path class="yzp037bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:map-marker" /></template>
