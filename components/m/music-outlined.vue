<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anzoiqb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anzoiqb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:music-outlined" /></template>
