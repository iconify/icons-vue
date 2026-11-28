<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t44j-ubxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="t44j-ubxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:monitor-slash" /></template>
