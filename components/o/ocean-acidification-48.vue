<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh24gkqan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kh24gkqan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ocean-acidification-48" /></template>
