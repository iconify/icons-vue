<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2b-a_j-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2b-a_j-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:outdoor-motion" /></template>
