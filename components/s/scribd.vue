<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6ghjjbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6ghjjbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:scribd" /></template>
