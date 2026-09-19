<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqdqp0n7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":224,"height":384};
const content = `<path class="gqdqp0n7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:money" /></template>
