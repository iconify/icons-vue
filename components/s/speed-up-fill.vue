<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se7a8gbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se7a8gbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:speed-up-fill" /></template>
