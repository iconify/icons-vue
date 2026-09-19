<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re-sap6xo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":448};
const content = `<path class="re-sap6xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:yahoo" /></template>
