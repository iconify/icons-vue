<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6n7lc_ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c6n7lc_ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:pinterest" /></template>
