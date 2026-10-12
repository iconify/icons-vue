<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yismpnbbv.css';
import '../../css/i/i2hk_6_pb.css';
import '../../css/i/iex7obabp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yismpnbbv"/><path class="i2hk_6_pb"/><path class="iex7obabp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:save-plus-filled" /></template>
