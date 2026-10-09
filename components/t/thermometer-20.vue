<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc18sub8n.css';
import '../../css/i/iuqdpw_hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gc18sub8n"/><path class="iuqdpw_hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermometer-20" /></template>
