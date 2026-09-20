<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqrvpqbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dqrvpqbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:stretching2" /></template>
