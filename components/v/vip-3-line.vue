<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwyl4jeby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwyl4jeby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vip-3-line" /></template>
