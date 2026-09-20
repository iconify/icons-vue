<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbon-80vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbon-80vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:signature-text" /></template>
