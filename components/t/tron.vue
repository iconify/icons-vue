<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxi8jpt5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lxi8jpt5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:tron" /></template>
