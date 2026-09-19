<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk_9v_7sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fk_9v_7sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ppe-suit" /></template>
