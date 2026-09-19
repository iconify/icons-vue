<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkt4d55tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dkt4d55tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:triangle-inverted-small-outline" /></template>
