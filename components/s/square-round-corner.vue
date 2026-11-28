<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nckoucbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nckoucbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-round-corner" /></template>
