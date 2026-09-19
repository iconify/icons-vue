<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t64z20bcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t64z20bcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:q2x-outline" /></template>
