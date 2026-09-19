<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq4iw6b1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="kq4iw6b1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:youtube-play" /></template>
