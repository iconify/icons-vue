<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2redwc5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f2redwc5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reddit-upvote" /></template>
