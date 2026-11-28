<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjkogcbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjkogcbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sunrise-solid" /></template>
