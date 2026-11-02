<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5a7kgjlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5a7kgjlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:photo-album-fill" /></template>
