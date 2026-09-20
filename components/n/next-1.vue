<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgsgssc1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qgsgssc1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:next-1" /></template>
