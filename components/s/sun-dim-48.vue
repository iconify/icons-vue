<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neup3sbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="neup3sbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-dim-48" /></template>
