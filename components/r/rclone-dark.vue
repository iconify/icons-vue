<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su3k7ebjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="su3k7ebjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rclone-dark" /></template>
