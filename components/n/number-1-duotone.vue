<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1b90xxfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1b90xxfz primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-1-duotone" /></template>
