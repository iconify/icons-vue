<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbws14nqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bbws14nqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:slide-show-play-solid" /></template>
