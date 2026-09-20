<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjv2x3bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjv2x3bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shield2-filled" /></template>
