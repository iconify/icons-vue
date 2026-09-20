<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iympo7t3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="iympo7t3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:voice-scan-2" /></template>
