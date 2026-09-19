<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngef1bydj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngef1bydj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pulse-01" /></template>
