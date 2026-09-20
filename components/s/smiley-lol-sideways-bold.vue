<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejos-9bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejos-9bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:smiley-lol-sideways-bold" /></template>
