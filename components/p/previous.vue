<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3u8k5bia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="g3u8k5bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:previous" /></template>
