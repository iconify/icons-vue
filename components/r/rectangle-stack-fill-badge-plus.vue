<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukg68oavl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ukg68oavl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-stack-fill-badge-plus" /></template>
