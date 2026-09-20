<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx_yp27iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mx_yp27iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:microphone-fill" /></template>
