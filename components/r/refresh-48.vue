<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz1-3kbvd.css';
import '../../css/k/kpheslb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yz1-3kbvd"/><path class="kpheslb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:refresh-48" /></template>
