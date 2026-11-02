<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snbezvl1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snbezvl1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:search-2-none-line" /></template>
