<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmxa-c6qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmxa-c6qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-terminal-solid" /></template>
