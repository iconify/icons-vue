<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x99ip2bfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x99ip2bfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:vidt" /></template>
