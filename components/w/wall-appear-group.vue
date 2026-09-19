<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7paadc1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7paadc1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wall-appear-group" /></template>
