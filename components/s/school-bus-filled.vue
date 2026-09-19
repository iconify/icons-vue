<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udwqky2ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udwqky2ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:school-bus-filled" /></template>
