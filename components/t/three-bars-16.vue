<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amy3jaclb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="amy3jaclb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:three-bars-16" /></template>
