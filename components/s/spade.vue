<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4y7kfbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4y7kfbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:spade" /></template>
