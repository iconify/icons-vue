<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4grcacqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j4grcacqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:phone" /></template>
