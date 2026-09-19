<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqtlj-uml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hqtlj-uml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:skip-backward-fill" /></template>
