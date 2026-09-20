<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsjj_hvfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsjj_hvfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:moon" /></template>
