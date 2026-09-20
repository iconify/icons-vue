<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_6--gbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q_6--gbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:two-finger-tap-solid" /></template>
