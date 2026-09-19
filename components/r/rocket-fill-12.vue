<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmq1eqdjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xmq1eqdjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:rocket-fill-12" /></template>
