<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb7cp6hix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cb7cp6hix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:village" /></template>
