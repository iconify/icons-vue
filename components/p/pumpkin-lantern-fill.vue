<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvivlccal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvivlccal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pumpkin-lantern-fill" /></template>
