<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iig5csjbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="iig5csjbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:notification-alarm-2" /></template>
