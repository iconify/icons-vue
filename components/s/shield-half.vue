<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg52cibag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg52cibag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-half" /></template>
