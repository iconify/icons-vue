<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edc_msbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="edc_msbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:signpost-split-fill" /></template>
