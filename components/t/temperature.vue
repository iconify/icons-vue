<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7xgi5bqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="f7xgi5bqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:temperature" /></template>
