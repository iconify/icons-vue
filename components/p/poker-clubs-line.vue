<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_e483b4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_e483b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:poker-clubs-line" /></template>
