<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh5m4gk5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sh5m4gk5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:person-48-bold" /></template>
