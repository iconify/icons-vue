<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt7epe3bo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="gt7epe3bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:spinner" /></template>
