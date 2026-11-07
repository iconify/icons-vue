<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/ts4ulcc5q.css';
import '../../css/v/vji9yqbmy.css';
import '../../css/y/yxpmksx3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ts4ulcc5q"/><path class="vji9yqbmy"/><path class="yxpmksx3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-rings-broken" /></template>
