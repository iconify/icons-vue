<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eppc3o07n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eppc3o07n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weather-partly-lightning" /></template>
