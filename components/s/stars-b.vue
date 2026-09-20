<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it92y3bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it92y3bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:stars-b" /></template>
