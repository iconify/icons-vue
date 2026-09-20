<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6t2-l6zm.css';
import '../../css/u/u6mx54sdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m6t2-l6zm"/><path class="u6mx54sdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:user-blocked" /></template>
