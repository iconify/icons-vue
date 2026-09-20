<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcl_b78rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcl_b78rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:phone-outgoing-line" /></template>
