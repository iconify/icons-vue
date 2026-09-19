<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogitdtbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="ogitdtbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rectangle-vertical-filled" /></template>
