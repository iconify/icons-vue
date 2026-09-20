<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbidn8bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xbidn8bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:optician-15" /></template>
