<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl9_jmpjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tl9_jmpjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:superscript" /></template>
