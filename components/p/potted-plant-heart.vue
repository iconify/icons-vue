<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4p49dj-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4p49dj-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:potted-plant-heart" /></template>
