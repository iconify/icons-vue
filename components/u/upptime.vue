<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmmu1j42j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmmu1j42j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:upptime" /></template>
