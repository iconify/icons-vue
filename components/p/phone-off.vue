<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxt2xwifj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxt2xwifj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:phone-off" /></template>
