<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm7fs1b4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hm7fs1b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:twitch" /></template>
