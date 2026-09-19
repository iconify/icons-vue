<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai7_7gb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ai7_7gb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:woman" /></template>
