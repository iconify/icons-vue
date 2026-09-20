<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i42t12bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i42t12bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:volume-low" /></template>
