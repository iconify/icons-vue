<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2--wegar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q2--wegar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-exception" /></template>
