<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye3a0wb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye3a0wb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-frame-2-broken" /></template>
