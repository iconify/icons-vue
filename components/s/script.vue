<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb5-xlblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb5-xlblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:script" /></template>
