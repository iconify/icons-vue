<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1h7svbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o1h7svbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:salad-48" /></template>
