<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqb1rcbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqb1rcbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xchf" /></template>
