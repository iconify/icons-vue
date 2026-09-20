<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfq14obvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nfq14obvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:spark-logo-block" /></template>
