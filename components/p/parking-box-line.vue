<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abysg8brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abysg8brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:parking-box-line" /></template>
