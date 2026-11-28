<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja0-wk5fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ja0-wk5fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:receipt-check" /></template>
