<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luymtsa7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="luymtsa7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-minus-fill" /></template>
