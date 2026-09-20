<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya8ta1jqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ya8ta1jqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:vector-square" /></template>
