<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfza_bc8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kfza_bc8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:smiley-frustrated-16" /></template>
