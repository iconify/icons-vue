<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvcghfbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvcghfbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tools-filled" /></template>
