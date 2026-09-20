<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfwzn80jq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfwzn80jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:store-filled" /></template>
