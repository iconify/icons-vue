<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw-kvgyje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw-kvgyje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:shield-line" /></template>
