<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxjxjk4sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxjxjk4sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-initial" /></template>
