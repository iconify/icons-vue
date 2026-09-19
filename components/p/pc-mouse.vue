<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efjpyloka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efjpyloka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:pc-mouse" /></template>
