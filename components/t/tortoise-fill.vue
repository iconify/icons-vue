<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_62_rb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="u_62_rb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tortoise-fill" /></template>
