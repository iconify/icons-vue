<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n47ky7pon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="n47ky7pon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:young-people" /></template>
