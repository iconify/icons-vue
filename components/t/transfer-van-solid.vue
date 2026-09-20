<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbqc9loyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lbqc9loyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:transfer-van-solid" /></template>
