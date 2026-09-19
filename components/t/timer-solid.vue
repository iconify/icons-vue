<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqt1wop1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kqt1wop1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:timer-solid" /></template>
