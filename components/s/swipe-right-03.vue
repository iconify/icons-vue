<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfzg1kbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfzg1kbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swipe-right-03" /></template>
