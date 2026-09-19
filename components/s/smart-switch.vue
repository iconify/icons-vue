<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxni506zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxni506zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:smart-switch" /></template>
