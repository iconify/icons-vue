<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn6g9f1_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn6g9f1_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mxlinux" /></template>
