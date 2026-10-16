<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgjsrykaw.css';
import '../../css/e/egp_zuxqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xgjsrykaw"/><path class="egp_zuxqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voltage-low-48" /></template>
