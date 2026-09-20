<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuu-qzuut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xuu-qzuut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:raven" /></template>
