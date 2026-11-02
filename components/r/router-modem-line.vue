<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3_secbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3_secbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:router-modem-line" /></template>
