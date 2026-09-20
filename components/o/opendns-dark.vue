<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxsv4ab9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xxsv4ab9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opendns-dark" /></template>
