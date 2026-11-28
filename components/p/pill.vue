<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti335245a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti335245a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:pill" /></template>
