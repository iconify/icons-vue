<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo3fzya9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo3fzya9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pause3" /></template>
