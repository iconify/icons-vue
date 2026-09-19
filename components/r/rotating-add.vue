<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne18dbc6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ne18dbc6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:rotating-add" /></template>
