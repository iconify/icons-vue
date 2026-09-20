<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icn400nlg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icn400nlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pagseguro" /></template>
