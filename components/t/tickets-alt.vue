<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osxrajb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="osxrajb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:tickets-alt" /></template>
