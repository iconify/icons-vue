<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw9q7j9hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bw9q7j9hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:table" /></template>
