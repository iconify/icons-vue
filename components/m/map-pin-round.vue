<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykrfa-b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykrfa-b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-round" /></template>
