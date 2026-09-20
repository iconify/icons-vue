<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7owgib4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="p7owgib4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:trend-down" /></template>
