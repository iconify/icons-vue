<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iynuj6bmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iynuj6bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-radical-light" /></template>
