<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmyu2ouwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmyu2ouwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:xing-logo" /></template>
