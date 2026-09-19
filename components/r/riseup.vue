<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpzi36bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jpzi36bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:riseup" /></template>
