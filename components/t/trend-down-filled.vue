<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgzsg8svi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgzsg8svi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:trend-down-filled" /></template>
