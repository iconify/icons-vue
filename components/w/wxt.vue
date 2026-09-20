<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kerqhwbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kerqhwbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:wxt" /></template>
