<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtx8_905u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtx8_905u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:shopping-sale" /></template>
