<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv3nwjbqk.css';
import '../../css/d/da5fxxb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="yv3nwjbqk"/><path class="da5fxxb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:shopping-basket" /></template>
