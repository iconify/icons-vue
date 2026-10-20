<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md-zhkn3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="md-zhkn3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:scanfile" /></template>
