<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hukx58fwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hukx58fwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tesla-icon" /></template>
