<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvc00ab_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="vvc00ab_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squarej" /></template>
