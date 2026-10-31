<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgbl2ybmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgbl2ybmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shirt-round" /></template>
