<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpef8vvsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lpef8vvsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:security-worker" /></template>
