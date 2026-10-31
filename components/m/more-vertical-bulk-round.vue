<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm5a0s0xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm5a0s0xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:more-vertical-bulk-round" /></template>
