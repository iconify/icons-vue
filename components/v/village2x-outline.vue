<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fytct9b5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fytct9b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:village2x-outline" /></template>
