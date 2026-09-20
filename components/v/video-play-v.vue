<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/armb_ptpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="armb_ptpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-play-v" /></template>
