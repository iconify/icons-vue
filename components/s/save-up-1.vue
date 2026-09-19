<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8xvvwglv.css';
import '../../css/p/p__g4pb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8xvvwglv"/><path class="p__g4pb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:save-up-1" /></template>
