<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmebglb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmebglb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:send-to-back-filled" /></template>
