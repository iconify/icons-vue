<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc9jzr62i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yc9jzr62i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ursa-major" /></template>
