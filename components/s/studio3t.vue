<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi2gyzb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi2gyzb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:studio3t" /></template>
