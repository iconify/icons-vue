<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlyu3-1bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlyu3-1bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:motorbike-fill" /></template>
