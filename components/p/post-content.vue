<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iaony-b0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iaony-b0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:post-content" /></template>
