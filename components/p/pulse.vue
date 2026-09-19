<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh1l-7bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh1l-7bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:pulse" /></template>
