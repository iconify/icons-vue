<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkewu7bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkewu7bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:send-to-back" /></template>
