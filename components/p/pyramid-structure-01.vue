<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjc8aza2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjc8aza2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pyramid-structure-01" /></template>
