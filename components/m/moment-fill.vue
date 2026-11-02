<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjc84i2ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjc84i2ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moment-fill" /></template>
