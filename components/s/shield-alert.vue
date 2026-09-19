<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuf4w3bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuf4w3bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:shield-alert" /></template>
