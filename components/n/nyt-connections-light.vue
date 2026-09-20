<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z40zwbc9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z40zwbc9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-connections-light" /></template>
