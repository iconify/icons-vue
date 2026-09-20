<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lme84c1eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lme84c1eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:mixer-horizontal" /></template>
