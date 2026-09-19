<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5rt3cb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f5rt3cb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:question-outline" /></template>
