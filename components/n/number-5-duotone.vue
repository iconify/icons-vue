<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2uhb_-xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2uhb_-xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-5-duotone" /></template>
