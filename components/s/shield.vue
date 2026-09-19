<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eccpoibnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":32};
const content = `<path class="eccpoibnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:shield" /></template>
