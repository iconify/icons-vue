<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0hu9nblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0hu9nblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:notebook-plus-outline" /></template>
