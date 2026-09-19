<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6pa94bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a6pa94bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-twitter-outline" /></template>
