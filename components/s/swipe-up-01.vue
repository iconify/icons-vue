<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slfwtsbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slfwtsbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swipe-up-01" /></template>
