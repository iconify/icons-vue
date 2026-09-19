<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp8fdwb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gp8fdwb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:wavy-check" /></template>
