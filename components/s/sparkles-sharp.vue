<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbr9q9ucb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qbr9q9ucb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:sparkles-sharp" /></template>
