<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_pniu6wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_pniu6wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stop-circle-outline" /></template>
