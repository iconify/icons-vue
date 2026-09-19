<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2qq1fjvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c2qq1fjvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:skip-start-fill" /></template>
