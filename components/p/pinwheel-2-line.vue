<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al3jz0dfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="al3jz0dfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pinwheel-2-line" /></template>
