<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no41bfb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no41bfb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:volume-broken" /></template>
