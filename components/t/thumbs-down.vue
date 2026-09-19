<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5qfizb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x5qfizb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:thumbs-down" /></template>
