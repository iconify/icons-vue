<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7dpgccnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="d7dpgccnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:nurse-assistant-emergency" /></template>
