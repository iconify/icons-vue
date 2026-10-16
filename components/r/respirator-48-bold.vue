<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsw62-7zd.css';
import '../../css/i/iib416bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bsw62-7zd"/><path class="iib416bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:respirator-48-bold" /></template>
