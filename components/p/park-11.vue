<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1hcn6bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="l1hcn6bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:park-11" /></template>
