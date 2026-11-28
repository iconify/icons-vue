<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-yr89biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-yr89biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:steam-train-solid" /></template>
