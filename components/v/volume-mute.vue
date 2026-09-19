<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2finz0wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2finz0wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:volume-mute" /></template>
