<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb_cr2bdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="rb_cr2bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:poll" /></template>
