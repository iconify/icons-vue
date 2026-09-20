<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cod50bpfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cod50bpfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:outline-ltr" /></template>
