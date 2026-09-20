<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqq221b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqq221b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:smoke-detector-outline" /></template>
