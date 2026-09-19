<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw7z-bckb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="bw7z-bckb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:youku" /></template>
