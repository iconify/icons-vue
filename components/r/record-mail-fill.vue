<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx01ajbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx01ajbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:record-mail-fill" /></template>
