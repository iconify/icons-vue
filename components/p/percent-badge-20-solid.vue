<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd-f8lbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="qd-f8lbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:percent-badge-20-solid" /></template>
