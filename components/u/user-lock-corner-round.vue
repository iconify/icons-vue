<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvx9cwb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvx9cwb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-lock-corner-round" /></template>
