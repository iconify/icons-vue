<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygcvb2b2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygcvb2b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:puzzle" /></template>
