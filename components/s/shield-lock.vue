<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuxsv2bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zuxsv2bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shield-lock" /></template>
