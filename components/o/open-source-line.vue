<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr3w9-lmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hr3w9-lmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:open-source-line" /></template>
