<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmzjqjb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmzjqjb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:skateboarding" /></template>
