<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8kyhtbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e8kyhtbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:square-small" /></template>
