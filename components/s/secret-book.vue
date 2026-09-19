<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni1s3p96w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ni1s3p96w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:secret-book" /></template>
