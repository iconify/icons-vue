<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1us_l5nc.css';
import '../../css/b/b7-x4wbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="g1us_l5nc"/><path class="b7-x4wbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:shadcn-ui-light" /></template>
