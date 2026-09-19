<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrms1vniq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrms1vniq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:microphone" /></template>
