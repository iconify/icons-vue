<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxveal41f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rxveal41f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:snapchat-dark" /></template>
