<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6zmte1wl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6zmte1wl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:th-menu" /></template>
