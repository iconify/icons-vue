<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdh90fr2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tdh90fr2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sparkles-48-bold" /></template>
