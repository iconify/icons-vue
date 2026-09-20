<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv7zo-lhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv7zo-lhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mihon" /></template>
