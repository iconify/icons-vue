<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy06uibqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy06uibqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:music-rest-eighth" /></template>
