<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6fitebpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6fitebpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rewind-duocolor-round" /></template>
