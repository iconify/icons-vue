<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah7jzxbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah7jzxbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tab-find" /></template>
