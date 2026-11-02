<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijrakd5dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijrakd5dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tyre-line" /></template>
