<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omesdvb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="omesdvb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reddit-upvote-light" /></template>
