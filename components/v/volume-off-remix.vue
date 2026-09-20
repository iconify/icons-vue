<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2e7dzr4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c2e7dzr4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:volume-off-remix" /></template>
