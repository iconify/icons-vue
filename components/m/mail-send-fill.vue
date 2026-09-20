<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofs8utivc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofs8utivc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mail-send-fill" /></template>
