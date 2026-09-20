<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-g6zlbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="t-g6zlbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:wasp" /></template>
