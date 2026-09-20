<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4r1jbbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4r1jbbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:system-regulation-filled" /></template>
