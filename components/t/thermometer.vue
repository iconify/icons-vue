<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fynwvgs9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fynwvgs9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:thermometer" /></template>
