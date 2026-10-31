<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a56926qld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a56926qld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:video-camera-arrow-up-right" /></template>
