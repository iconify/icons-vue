<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muk07ebbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="muk07ebbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:mental-disorders" /></template>
