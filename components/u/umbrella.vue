<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eefks2b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eefks2b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:umbrella" /></template>
