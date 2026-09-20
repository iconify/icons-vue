<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s55_9jckw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s55_9jckw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-play-h" /></template>
