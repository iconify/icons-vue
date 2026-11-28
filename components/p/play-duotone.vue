<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s58z6bw5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary s58z6bw5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:play-duotone" /></template>
