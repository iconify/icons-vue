<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zizp4pbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zizp4pbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:sine" /></template>
