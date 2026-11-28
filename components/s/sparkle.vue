<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryi59f59s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryi59f59s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sparkle" /></template>
