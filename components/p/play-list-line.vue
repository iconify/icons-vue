<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgul6q2_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgul6q2_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:play-list-line" /></template>
