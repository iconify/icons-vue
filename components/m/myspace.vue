<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1jiskbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":448};
const content = `<path class="z1jiskbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:myspace" /></template>
