<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwq2k-b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1472};
const content = `<path class="rwq2k-b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:user-waiter" /></template>
