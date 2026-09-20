<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s53ifu8-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s53ifu8-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:rocket-24" /></template>
