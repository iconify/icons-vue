<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrv_jrbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrv_jrbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:megaphone" /></template>
