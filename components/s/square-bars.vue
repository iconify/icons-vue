<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8crd06px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n8crd06px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:square-bars" /></template>
