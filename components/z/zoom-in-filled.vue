<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-n0pf_-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-n0pf_-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:zoom-in-filled" /></template>
