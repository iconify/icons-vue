<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh2130lxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh2130lxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:myanimelist" /></template>
