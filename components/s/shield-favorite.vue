<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2c72nr_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2c72nr_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-favorite" /></template>
