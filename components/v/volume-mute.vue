<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdjmgxbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":192,"height":384};
const content = `<path class="sdjmgxbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:volume-mute" /></template>
