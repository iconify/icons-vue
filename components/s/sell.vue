<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6gwpacru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="u6gwpacru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:sell" /></template>
