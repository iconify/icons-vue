<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2lhz8f1q.css';
import '../../css/v/vnjnmccnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2lhz8f1q"/><path class="vnjnmccnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:star-check-filled" /></template>
