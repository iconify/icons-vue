<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tssr405-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tssr405-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:unlike" /></template>
