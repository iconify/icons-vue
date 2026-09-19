<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-abih8ua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-abih8ua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sr-radio" /></template>
