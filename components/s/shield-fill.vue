<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zje8ikb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zje8ikb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shield-fill" /></template>
