<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjtmb3b2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjtmb3b2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:star-slash" /></template>
