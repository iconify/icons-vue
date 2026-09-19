<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amqcs7bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="amqcs7bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:yahoo2" /></template>
