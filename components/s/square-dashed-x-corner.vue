<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2l5l7vvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2l5l7vvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-dashed-x-corner" /></template>
