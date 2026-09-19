<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsds9abwl.css';
import '../../css/i/ixvh0acwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tsds9abwl"/><path clip-rule="evenodd" class="ixvh0acwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:volume-2-outline" /></template>
