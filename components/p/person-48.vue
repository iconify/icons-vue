<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8slav1si.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b8slav1si"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:person-48" /></template>
