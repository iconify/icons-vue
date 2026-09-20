<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smnye9b4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smnye9b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:terminal-asterisk-sharp-fill" /></template>
