<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srgjyix3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srgjyix3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:venus-sharp" /></template>
