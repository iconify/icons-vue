<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru_8w8f1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru_8w8f1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:panoramic" /></template>
