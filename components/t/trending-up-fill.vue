<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmq-2ccok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmq-2ccok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:trending-up-fill" /></template>
