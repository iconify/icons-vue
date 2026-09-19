<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg2rmmb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hg2rmmb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:rocket" /></template>
