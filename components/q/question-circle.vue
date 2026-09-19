<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctndx5h7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ctndx5h7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:question-circle" /></template>
