<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdxa_275p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdxa_275p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:martini-filled" /></template>
