<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlwl73qmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlwl73qmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pkt" /></template>
