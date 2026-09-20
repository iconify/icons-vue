<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvbplbcfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="cvbplbcfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:speechbubble" /></template>
