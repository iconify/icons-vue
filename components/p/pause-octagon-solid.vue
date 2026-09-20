<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2g541tdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2g541tdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:pause-octagon-solid" /></template>
