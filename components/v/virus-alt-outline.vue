<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co-40o1eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="co-40o1eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:virus-alt-outline" /></template>
