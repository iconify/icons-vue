<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqjpjy1gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mqjpjy1gs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:surgical-sterilization2x-outline" /></template>
