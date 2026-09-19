<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2p5uybkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d2p5uybkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:video-camera-plus" /></template>
