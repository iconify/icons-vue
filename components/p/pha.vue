<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzg73qn1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yzg73qn1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pha" /></template>
