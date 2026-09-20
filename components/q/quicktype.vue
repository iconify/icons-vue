<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-fpo2tmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-fpo2tmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:quicktype" /></template>
