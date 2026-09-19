<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrqf8_bpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrqf8_bpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:zsh" /></template>
