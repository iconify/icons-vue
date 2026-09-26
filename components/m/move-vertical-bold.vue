<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqg0xy6-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqg0xy6-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-vertical-bold" /></template>
