<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgztnybqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tgztnybqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:ruler-vertical" /></template>
