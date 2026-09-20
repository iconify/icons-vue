<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dktm0rvez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dktm0rvez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:zodiac-pisces" /></template>
