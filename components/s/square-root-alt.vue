<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz16embsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="qz16embsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:square-root-alt" /></template>
