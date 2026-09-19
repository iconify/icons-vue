<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr_oyr2ju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tr_oyr2ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:suitcase-fill" /></template>
