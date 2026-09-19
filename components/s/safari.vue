<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk36d2bsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uk36d2bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:safari" /></template>
