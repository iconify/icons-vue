<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkuw3r.css';
import '../../css/s/so-from-66.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkuw3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:square" /></template>
