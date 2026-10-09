<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozrn3bc7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ozrn3bc7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:swimming-48-bold" /></template>
