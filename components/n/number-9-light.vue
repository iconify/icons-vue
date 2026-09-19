<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijozgdbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijozgdbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-9-light" /></template>
