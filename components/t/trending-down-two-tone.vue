<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrix8ccrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrix8ccrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:trending-down-two-tone" /></template>
