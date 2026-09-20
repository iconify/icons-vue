<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7uz5csis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j7uz5csis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:roman-numeral-iii" /></template>
