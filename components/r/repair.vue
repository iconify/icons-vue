<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn7qp0y5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tn7qp0y5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:repair" /></template>
