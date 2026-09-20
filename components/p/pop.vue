<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw--h24ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw--h24ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pop" /></template>
