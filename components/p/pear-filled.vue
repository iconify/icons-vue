<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfoehcc9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfoehcc9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:pear-filled" /></template>
