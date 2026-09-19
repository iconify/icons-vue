<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3df0d7pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3df0d7pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:road-filled" /></template>
