<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqe4w3b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqe4w3b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:radar-2-broken" /></template>
