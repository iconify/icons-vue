<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crd2_n-ve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crd2_n-ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:red-packet-line" /></template>
