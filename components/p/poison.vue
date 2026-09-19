<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj2h62b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nj2h62b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:poison" /></template>
