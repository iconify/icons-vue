<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c98j8rb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c98j8rb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:symbol-enum-member" /></template>
