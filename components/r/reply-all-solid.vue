<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btcv4zsiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btcv4zsiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:reply-all-solid" /></template>
