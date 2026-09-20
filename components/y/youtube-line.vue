<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0xhp2b-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0xhp2b-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:youtube-line" /></template>
