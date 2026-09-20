<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq3np2bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rq3np2bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:yen-circle-line" /></template>
