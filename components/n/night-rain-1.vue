<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avsdhy2ld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avsdhy2ld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:night-rain-1" /></template>
