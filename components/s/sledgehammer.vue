<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb2dvngzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rb2dvngzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:sledgehammer" /></template>
