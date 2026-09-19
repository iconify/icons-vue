<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx7tqac6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gx7tqac6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:whip" /></template>
