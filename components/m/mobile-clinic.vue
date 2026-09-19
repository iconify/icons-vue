<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3wbfm8wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="y3wbfm8wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:mobile-clinic" /></template>
