<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f22o04bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f22o04bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:panoramas-line" /></template>
