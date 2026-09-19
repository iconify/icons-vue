<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnjstib_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cnjstib_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:plugin" /></template>
