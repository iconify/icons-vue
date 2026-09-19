<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srg4cibox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="srg4cibox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:news" /></template>
