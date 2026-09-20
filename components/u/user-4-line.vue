<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fytl7572t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fytl7572t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-4-line" /></template>
