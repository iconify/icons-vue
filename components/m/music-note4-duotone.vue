<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-ttllwtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-ttllwtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:music-note4-duotone" /></template>
