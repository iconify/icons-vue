<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fptu3rb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fptu3rb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:minus" /></template>
