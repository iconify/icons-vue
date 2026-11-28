<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_1kf0icu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_1kf0icu primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zodiac-cancer-duotone" /></template>
