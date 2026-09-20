<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrbcqbcia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrbcqbcia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:reuni" /></template>
