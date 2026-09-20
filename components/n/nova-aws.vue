<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erxn25bjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":33,"height":32};
const content = `<path class="erxn25bjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nova-aws" /></template>
