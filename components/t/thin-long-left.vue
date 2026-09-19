<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x36tgtxbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x36tgtxbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:thin-long-left" /></template>
