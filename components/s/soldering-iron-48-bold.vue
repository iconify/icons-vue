<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aft-_hbdu.css';
import '../../css/i/i-s48fubu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aft-_hbdu"/><path class="i-s48fubu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:soldering-iron-48-bold" /></template>
