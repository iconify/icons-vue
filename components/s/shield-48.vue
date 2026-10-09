<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lld64mb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lld64mb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-48" /></template>
