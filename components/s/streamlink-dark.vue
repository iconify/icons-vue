<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvq4twb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mvq4twb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:streamlink-dark" /></template>
