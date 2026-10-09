<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adswyhb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="adswyhb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-48-bold" /></template>
