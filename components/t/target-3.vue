<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnmy-k-kq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnmy-k-kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:target-3" /></template>
