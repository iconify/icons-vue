<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk1u7ubxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk1u7ubxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:substack-fill" /></template>
