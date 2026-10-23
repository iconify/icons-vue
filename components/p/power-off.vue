<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf8efqbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf8efqbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:power-off" /></template>
