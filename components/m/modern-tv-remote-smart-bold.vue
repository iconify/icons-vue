<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyx3iwnif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyx3iwnif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:modern-tv-remote-smart-bold" /></template>
