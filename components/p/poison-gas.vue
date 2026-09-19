<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1n722con.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j1n722con"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:poison-gas" /></template>
