<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv99tik4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv99tik4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:video-player-movie-bold" /></template>
