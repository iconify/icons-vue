<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox1429anc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox1429anc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mind-map-fill" /></template>
