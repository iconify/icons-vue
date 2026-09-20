<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh49b7bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh49b7bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:textbox-fill" /></template>
