<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kai_8tblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kai_8tblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:music-slider" /></template>
