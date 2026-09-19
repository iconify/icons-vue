<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpzch7b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cpzch7b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:pill-1" /></template>
