<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4ldhpg5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4ldhpg5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pubg" /></template>
