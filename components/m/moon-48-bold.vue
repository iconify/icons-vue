<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exve3kbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="exve3kbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moon-48-bold" /></template>
