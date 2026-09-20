<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb69-0b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb69-0b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:volume-1" /></template>
