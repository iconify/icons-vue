<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtly1zbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":702,"height":704};
const content = `<path class="gtly1zbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:ubuntu" /></template>
