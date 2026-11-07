<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq2hqvwyz.css';
import '../../css/q/q5070xbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq2hqvwyz"/><path class="q5070xbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-to-folder-bold-duotone" /></template>
