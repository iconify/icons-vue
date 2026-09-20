<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjwarlp5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cjwarlp5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:memories-dark" /></template>
