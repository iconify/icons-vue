<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttxsexshj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttxsexshj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-alphabetical-descending-variant" /></template>
