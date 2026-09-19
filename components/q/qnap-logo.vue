<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2d0-mhrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2d0-mhrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:qnap-logo" /></template>
