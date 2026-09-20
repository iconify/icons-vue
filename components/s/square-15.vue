<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4bhkzb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l4bhkzb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:square-15" /></template>
