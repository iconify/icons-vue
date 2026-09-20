<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6hd68ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x6hd68ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:snow" /></template>
