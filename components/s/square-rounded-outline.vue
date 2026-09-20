<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdxwq8bbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdxwq8bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:square-rounded-outline" /></template>
