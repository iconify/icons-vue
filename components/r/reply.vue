<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuu-4lnlt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuu-4lnlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:reply" /></template>
