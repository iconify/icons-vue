<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioxi_abwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ioxi_abwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-diving" /></template>
