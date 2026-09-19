<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei4r2welx.css';
import '../../css/n/nt_i2cb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei4r2welx"/><path class="nt_i2cb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:power" /></template>
