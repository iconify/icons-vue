<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxtgz5blq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oxtgz5blq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:upvote-rss-dark" /></template>
