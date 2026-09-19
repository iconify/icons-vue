<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adklw4bna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adklw4bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:signal-5" /></template>
