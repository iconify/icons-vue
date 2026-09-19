<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0585hlis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="p0585hlis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:pass-compact" /></template>
