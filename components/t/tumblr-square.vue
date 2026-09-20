<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd9wi1d8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd9wi1d8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:tumblr-square" /></template>
