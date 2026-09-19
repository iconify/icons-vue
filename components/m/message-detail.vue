<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txisfl_qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txisfl_qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:message-detail" /></template>
