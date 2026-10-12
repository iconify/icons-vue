<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxm7d5bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hxm7d5bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:parenthesis-20" /></template>
