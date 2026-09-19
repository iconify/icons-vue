<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd5t3ac2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fd5t3ac2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:skateboarding-02" /></template>
