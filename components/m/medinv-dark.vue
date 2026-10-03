<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv5t23ldk.css';
import '../../css/o/oqpqr4qja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vv5t23ldk"/><circle class="oqpqr4qja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:medinv-dark" /></template>
