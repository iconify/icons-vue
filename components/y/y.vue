<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3_h01beb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r3_h01beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:y" /></template>
