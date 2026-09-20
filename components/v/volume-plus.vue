<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4le9wpeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4le9wpeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:volume-plus" /></template>
