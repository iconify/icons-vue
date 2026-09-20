<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tujk-ablr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tujk-ablr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:minimize-one" /></template>
