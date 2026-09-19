<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p35kmxb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="p35kmxb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:square-lastfm" /></template>
