<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlx0s_w4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlx0s_w4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:send-off" /></template>
