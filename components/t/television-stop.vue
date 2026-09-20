<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch5nr5ubw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch5nr5ubw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:television-stop" /></template>
