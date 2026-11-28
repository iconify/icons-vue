<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7_41vbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7_41vbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shapes-solid" /></template>
