<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5v9h6b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":416,"height":472};
const content = `<path class="e5v9h6b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:warning" /></template>
