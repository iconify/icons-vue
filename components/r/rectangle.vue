<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhid8bcga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jhid8bcga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:rectangle" /></template>
