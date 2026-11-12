<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evm6bqe-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="evm6bqe-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:newsblur-dark" /></template>
