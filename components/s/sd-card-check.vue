<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nygdq9b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nygdq9b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:sd-card-check" /></template>
