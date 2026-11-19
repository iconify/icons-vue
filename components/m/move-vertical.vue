<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njuxs6bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njuxs6bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:move-vertical" /></template>
