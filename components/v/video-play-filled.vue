<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzd4rrbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzd4rrbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-play-filled" /></template>
