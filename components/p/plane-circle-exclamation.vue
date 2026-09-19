<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-681ibkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="m-681ibkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:plane-circle-exclamation" /></template>
