<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llv_5bi1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llv_5bi1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:moon-haze-solid" /></template>
