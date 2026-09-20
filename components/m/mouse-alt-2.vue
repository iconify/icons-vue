<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgoclccam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgoclccam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:mouse-alt-2" /></template>
