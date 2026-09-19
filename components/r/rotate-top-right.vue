<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck_0vwbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck_0vwbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rotate-top-right" /></template>
