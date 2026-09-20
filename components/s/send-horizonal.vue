<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5a7x8bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5a7x8bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:send-horizonal" /></template>
