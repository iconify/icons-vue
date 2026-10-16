<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5b617bur.css';
import '../../css/i/ihmii9b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o5b617bur"/><path class="ihmii9b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tank-farm-48-bold" /></template>
