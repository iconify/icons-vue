<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7feoacqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t7feoacqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-rowing-rowboat-on-water" /></template>
