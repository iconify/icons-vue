<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx-8u-k7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx-8u-k7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:server-refresh" /></template>
