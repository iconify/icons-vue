<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmaryiywy.css';
import '../../css/y/ytqlk8bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wmaryiywy"/><path class="ytqlk8bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:traffic-light-20" /></template>
