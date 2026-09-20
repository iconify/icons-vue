<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlzp8hbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlzp8hbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:stack-overflow" /></template>
