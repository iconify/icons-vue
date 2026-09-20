<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn25p6lzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sn25p6lzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:volume-up-line" /></template>
