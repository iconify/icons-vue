<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-fqx2gsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="s-fqx2gsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:thermometer" /></template>
