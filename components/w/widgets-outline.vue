<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwp63zbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwp63zbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:widgets-outline" /></template>
