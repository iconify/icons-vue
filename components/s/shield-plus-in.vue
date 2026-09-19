<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7qaq_brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7qaq_brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:shield-plus-in" /></template>
