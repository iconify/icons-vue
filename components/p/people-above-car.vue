<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7port6eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d7port6eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:people-above-car" /></template>
