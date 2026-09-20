<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd4ttjned.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd4ttjned"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:rocket-filled" /></template>
