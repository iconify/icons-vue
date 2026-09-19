<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il6iivpjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il6iivpjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tilt-window-opened" /></template>
