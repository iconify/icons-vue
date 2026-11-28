<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh99xablo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jh99xablo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:traffic-cone" /></template>
