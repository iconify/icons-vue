<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aow7gkdrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="aow7gkdrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:video-camera-record-filled" /></template>
