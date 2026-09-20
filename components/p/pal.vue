<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efhud-bfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efhud-bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pal" /></template>
