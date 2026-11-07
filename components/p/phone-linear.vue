<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aamohydpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aamohydpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:phone-linear" /></template>
