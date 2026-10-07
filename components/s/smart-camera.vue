<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv5kl0b9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv5kl0b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:smart-camera" /></template>
