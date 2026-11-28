<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy1wcmb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy1wcmb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:network-alert" /></template>
