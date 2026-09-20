<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec060xbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ec060xbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:piggy-bank-outline" /></template>
