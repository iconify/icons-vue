<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x30s24-dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x30s24-dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrow-left-up" /></template>
