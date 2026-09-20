<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edrcmr_wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="edrcmr_wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:russian-orthodox-cross" /></template>
