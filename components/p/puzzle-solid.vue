<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u65bls48j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u65bls48j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:puzzle-solid" /></template>
