<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6cxkxoqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6cxkxoqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:volume-minus-solid" /></template>
