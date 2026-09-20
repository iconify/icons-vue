<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys_em6wiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys_em6wiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:zoom-out-outline" /></template>
