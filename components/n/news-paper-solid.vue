<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjtwk6_ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xjtwk6_ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:news-paper-solid" /></template>
