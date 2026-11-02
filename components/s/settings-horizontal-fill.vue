<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdrsw6b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdrsw6b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:settings-horizontal-fill" /></template>
