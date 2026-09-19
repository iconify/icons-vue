<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpsk3tlwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dpsk3tlwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:moon-stroke-12" /></template>
