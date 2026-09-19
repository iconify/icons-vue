<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iivu8_blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iivu8_blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:popsicle-filled" /></template>
