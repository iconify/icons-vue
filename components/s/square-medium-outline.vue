<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsu2q7bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bsu2q7bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:square-medium-outline" /></template>
