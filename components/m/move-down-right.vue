<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbz6o0bkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbz6o0bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:move-down-right" /></template>
