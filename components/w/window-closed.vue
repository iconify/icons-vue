<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcgm34bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcgm34bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:window-closed" /></template>
