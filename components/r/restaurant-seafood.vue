<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipb0gbcjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ipb0gbcjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:restaurant-seafood" /></template>
