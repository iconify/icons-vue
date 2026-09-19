<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpwy_ackl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="qpwy_ackl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:n-upper-case" /></template>
