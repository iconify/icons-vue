<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl9l-cbsp.css';
import '../../css/p/pejn30ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl9l-cbsp"/><path class="pejn30ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:network-signal-bold" /></template>
