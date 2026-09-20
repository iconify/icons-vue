<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2c9rdnyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2c9rdnyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:shield-ellipsis" /></template>
