<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh1eqybkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":33,"height":32};
const content = `<path class="lh1eqybkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:nova-aws" /></template>
