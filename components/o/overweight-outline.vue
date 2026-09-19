<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_6hrubaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="n_6hrubaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:overweight-outline" /></template>
