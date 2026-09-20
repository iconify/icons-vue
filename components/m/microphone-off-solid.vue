<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z30xycbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z30xycbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:microphone-off-solid" /></template>
