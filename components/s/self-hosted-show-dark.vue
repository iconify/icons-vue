<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z182-6axt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z182-6axt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:self-hosted-show-dark" /></template>
