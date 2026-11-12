<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_2v1ybsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a_2v1ybsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:streamlink-dark" /></template>
