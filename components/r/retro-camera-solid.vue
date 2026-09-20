<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpk6ggg_n.css';
import '../../css/n/ndqxj1bdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpk6ggg_n"/><path class="ndqxj1bdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:retro-camera-solid" /></template>
