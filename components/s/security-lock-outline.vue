<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ummc0db4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ummc0db4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:security-lock-outline" /></template>
