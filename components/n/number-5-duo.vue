<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k124hfb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k124hfb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-5-duo" /></template>
