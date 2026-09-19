<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n249hpp4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n249hpp4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swipe-down-05" /></template>
