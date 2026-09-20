<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f44xqac4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f44xqac4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:scrapy" /></template>
