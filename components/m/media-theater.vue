<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7fphkwmy.css';
import '../../css/e/eytrnn8dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7fphkwmy"/><path class="eytrnn8dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-theater" /></template>
