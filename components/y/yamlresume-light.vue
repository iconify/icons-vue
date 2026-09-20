<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez0hwtbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ez0hwtbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yamlresume-light" /></template>
