<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls0-ekloj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ls0-ekloj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:note" /></template>
