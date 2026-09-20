<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnff0lbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnff0lbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:riotgames" /></template>
