<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swhsg8bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="swhsg8bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:spray" /></template>
