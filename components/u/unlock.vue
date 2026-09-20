<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4s8bybvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q4s8bybvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:unlock" /></template>
