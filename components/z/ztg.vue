<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfy5v1ddq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfy5v1ddq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ztg" /></template>
