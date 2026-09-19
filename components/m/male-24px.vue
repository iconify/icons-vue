<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol_w2hbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ol_w2hbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:male-24px" /></template>
