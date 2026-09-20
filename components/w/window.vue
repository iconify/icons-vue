<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qugdhub4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="qugdhub4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:window" /></template>
