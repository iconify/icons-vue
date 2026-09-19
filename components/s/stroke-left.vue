<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2u4fjgnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2u4fjgnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:stroke-left" /></template>
