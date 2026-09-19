<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4wb5_did.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k4wb5_did"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:unarchive" /></template>
