<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac_kg-bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac_kg-bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:movie-line" /></template>
