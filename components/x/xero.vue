<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btg86dbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="btg86dbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:xero" /></template>
