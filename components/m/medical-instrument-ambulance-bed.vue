<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czzkhvbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czzkhvbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:medical-instrument-ambulance-bed" /></template>
