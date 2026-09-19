<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3ai75bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="q3ai75bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:twitter" /></template>
