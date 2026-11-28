<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1ejkacuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1ejkacuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:overline-solid" /></template>
