<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqi4ufqbo.css';
import '../../css/y/ylqfvzsqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rqi4ufqbo"/><path class="ylqfvzsqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:nutrition-sharp" /></template>
