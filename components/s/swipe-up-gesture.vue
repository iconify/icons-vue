<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/payqtdb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="payqtdb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:swipe-up-gesture" /></template>
