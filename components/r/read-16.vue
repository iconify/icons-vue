<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnujzj9yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pnujzj9yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:read-16" /></template>
