<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6z1-7bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6z1-7bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:oura-o" /></template>
