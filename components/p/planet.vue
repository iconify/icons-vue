<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv2cl-bjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":641};
const content = `<path class="gv2cl-bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:planet" /></template>
