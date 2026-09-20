<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzm7f0b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzm7f0b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:the-models-resource" /></template>
