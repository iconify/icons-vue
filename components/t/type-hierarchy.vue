<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af1jcmpkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="af1jcmpkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:type-hierarchy" /></template>
