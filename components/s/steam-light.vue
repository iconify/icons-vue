<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euhhj_9fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="euhhj_9fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:steam-light" /></template>
