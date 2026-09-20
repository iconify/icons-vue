<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn5s0kk9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nn5s0kk9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rounded-triangle-up" /></template>
