<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvr9_mbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvr9_mbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:vials" /></template>
