<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xox_g4bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xox_g4bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:signal-slash" /></template>
