<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idb_0ybwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="idb_0ybwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:up-two" /></template>
