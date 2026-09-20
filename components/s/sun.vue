<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kol8oy98e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kol8oy98e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:sun" /></template>
