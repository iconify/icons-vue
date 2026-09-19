<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7p_7vbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7p_7vbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sailboat-coastal" /></template>
