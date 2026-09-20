<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdnxlnb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdnxlnb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sequence-filled" /></template>
