<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x__byqb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x__byqb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:ship-wheel" /></template>
