<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj9cadb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oj9cadb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:share" /></template>
