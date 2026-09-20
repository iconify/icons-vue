<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldfk44b2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ldfk44b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:mountain-cross" /></template>
