<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs4gt46wn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs4gt46wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wall-tuar" /></template>
