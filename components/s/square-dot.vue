<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0u61gmvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a0u61gmvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:square-dot" /></template>
