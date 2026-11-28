<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzih8sb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzih8sb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tally-1-solid" /></template>
