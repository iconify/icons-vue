<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qikil81ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qikil81ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:shortcode" /></template>
