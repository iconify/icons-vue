<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sma0iqctz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sma0iqctz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:stop-square-fill" /></template>
