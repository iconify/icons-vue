<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln2cx2igb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln2cx2igb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:scissors-solid" /></template>
