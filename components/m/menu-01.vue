<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs543877e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs543877e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:menu-01" /></template>
