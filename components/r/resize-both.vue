<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en0dhbq2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="en0dhbq2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:resize-both" /></template>
