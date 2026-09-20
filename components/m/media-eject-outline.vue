<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8a64dbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8a64dbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:media-eject-outline" /></template>
