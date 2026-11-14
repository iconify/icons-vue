<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryvkt82sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryvkt82sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pound-receive" /></template>
