<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8pyggqfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f8pyggqfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-wearing-racing-helmet-driving-go-kart" /></template>
