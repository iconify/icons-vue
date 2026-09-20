<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whg_0cbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="whg_0cbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:quiet" /></template>
