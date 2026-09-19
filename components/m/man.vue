<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0lxhccly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p0lxhccly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:man" /></template>
