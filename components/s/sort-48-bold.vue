<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oljuiobcr.css';
import '../../css/e/eecmlgb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oljuiobcr"/><path class="eecmlgb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sort-48-bold" /></template>
