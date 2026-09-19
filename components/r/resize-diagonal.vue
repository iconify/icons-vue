<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqs_9zbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uqs_9zbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:resize-diagonal" /></template>
