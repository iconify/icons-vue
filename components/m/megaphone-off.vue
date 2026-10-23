<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpcszgbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpcszgbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:megaphone-off" /></template>
