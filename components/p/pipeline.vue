<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj0y7_bid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj0y7_bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pipeline" /></template>
