<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv254yk6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gv254yk6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:triangle-inverted-large" /></template>
