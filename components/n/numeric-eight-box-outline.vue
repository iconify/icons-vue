<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdtwd7bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdtwd7bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-eight-box-outline" /></template>
