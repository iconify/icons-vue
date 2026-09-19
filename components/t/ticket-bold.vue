<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7q8q5bpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7q8q5bpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:ticket-bold" /></template>
