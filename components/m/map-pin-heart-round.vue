<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls5zy66mw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls5zy66mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-heart-round" /></template>
