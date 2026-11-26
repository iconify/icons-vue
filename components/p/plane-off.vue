<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh5t2rbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh5t2rbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:plane-off" /></template>
