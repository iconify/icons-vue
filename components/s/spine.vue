<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0cbi43ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t0cbi43ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:spine" /></template>
