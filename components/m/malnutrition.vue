<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh_w3wmue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gh_w3wmue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:malnutrition" /></template>
