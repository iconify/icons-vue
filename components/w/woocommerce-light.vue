<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4e7os4sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e4e7os4sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:woocommerce-light" /></template>
