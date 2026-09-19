<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtm7eswgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1600};
const content = `<path class="xtm7eswgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:umbrella" /></template>
