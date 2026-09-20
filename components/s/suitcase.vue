<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo9gk5brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eo9gk5brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:suitcase" /></template>
