<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aija5746l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aija5746l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shoe-cleat" /></template>
