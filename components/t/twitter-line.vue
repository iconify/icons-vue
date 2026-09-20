<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueg_mznks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ueg_mznks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:twitter-line" /></template>
