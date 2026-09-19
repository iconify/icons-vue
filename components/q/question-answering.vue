<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcunifpot.css';
import '../../css/z/zgaui9bdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xcunifpot"/><path class="zgaui9bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:question-answering" /></template>
