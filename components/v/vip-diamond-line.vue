<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyhql9blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyhql9blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:vip-diamond-line" /></template>
