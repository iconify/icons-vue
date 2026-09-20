<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk9brtb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xk9brtb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search-plus4-filled" /></template>
