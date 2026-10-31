<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3hl5yb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s3hl5yb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:video-camera-arrow-up-right-solid" /></template>
