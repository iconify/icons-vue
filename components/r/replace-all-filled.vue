<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9bw8kbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9bw8kbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:replace-all-filled" /></template>
