<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kql4cwbwx.css';
import '../../css/t/td28wmbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kql4cwbwx"/><path class="td28wmbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:product-hunt" /></template>
