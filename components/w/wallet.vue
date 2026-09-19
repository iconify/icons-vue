<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umk1w0oyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="umk1w0oyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:wallet" /></template>
