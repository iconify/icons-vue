<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrh1ln4gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrh1ln4gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sunset-line" /></template>
