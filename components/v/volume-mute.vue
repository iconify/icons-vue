<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6_o05b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6_o05b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:volume-mute" /></template>
