<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya8ajib9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ya8ajib9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:wlan-strength-2-lock" /></template>
