<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upq7dqbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="upq7dqbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:tailwindcss" /></template>
