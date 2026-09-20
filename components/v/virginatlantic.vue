<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxmyj_bxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxmyj_bxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:virginatlantic" /></template>
