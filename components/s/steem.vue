<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2a1q1bpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2a1q1bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:steem" /></template>
