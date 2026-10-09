<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq6s4g74y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oq6s4g74y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stop-48-bold" /></template>
