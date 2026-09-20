<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/depz1ebrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="depz1ebrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sina-weibo" /></template>
